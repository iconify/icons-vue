<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyto8pb-r.css';
import '../../css/q/qq9jsubwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gyto8pb-r"/><path class="qq9jsubwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:port-input" /></template>
