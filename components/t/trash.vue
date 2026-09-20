<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/d/dq2v5k.css';
import '../../css/z/zo85jt.css';
import '../../css/w/wzg25p.css';
import '../../css/s/so-from-24.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c dq2v5k"/><path class="a0m25c zo85jt"/><path class="a0m25c wzg25p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:trash" /></template>
