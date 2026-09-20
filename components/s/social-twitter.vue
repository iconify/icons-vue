<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl5r9mbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl5r9mbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:social-twitter" /></template>
