<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-ca_himm.css';
import '../../css/c/czogqxb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h-ca_himm"/><path class="czogqxb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:mute" /></template>
