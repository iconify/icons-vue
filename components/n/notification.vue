<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smsq4b2xo.css';
import '../../css/a/amoelnz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="smsq4b2xo"/><path class="amoelnz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:notification" /></template>
