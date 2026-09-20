<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc-f_171e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc-f_171e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:social-twitter-solid" /></template>
