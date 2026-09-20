<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/corykn.css';
import '../../css/n/nhjobb.css';
import '../../css/s/so-from-70.css';
import '../../css/d/d-4c0-hc.css';
import '../../css/d/d-i58k3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="corykn"/><path class="nhjobb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:tablet" /></template>
