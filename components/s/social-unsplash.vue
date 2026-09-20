<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p06tlqbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p06tlqbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:social-unsplash" /></template>
