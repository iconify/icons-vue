<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax9gbu_0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ax9gbu_0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:mastodon-filled" /></template>
