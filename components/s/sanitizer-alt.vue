<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkonw3bdh.css';
import '../../css/s/skxq2dbrt.css';
import '../../css/g/g6shut3wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkonw3bdh"/><path class="skxq2dbrt"/><path class="g6shut3wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:sanitizer-alt" /></template>
