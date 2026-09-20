<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zofucd4sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zofucd4sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:toml" /></template>
