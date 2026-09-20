<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msm96vi3m.css';
import '../../css/h/hstvx30-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msm96vi3m"/><path class="hstvx30-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:payment-link-solid" /></template>
