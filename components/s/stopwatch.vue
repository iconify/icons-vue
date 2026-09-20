<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob6wv6w5p.css';
import '../../css/o/olze3bcsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob6wv6w5p"/><path clip-rule="evenodd" class="olze3bcsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:stopwatch" /></template>
