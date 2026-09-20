<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/w/wonoqj.css';
import '../../css/x/xzxtaq.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c wonoqj"/><path class="a0m25c xzxtaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:person" /></template>
