<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8uw2mboa.css';
import '../../css/p/psr8s7bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="b8uw2mboa"/><path class="psr8s7bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:super-productivity" /></template>
