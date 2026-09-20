<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5ueyub-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a5ueyub-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:nfc-fill" /></template>
