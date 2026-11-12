<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o52kqiium.css';
import '../../css/k/kcinj1bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o52kqiium"/><path class="kcinj1bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oauth2-proxy-dark" /></template>
