<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brno_ib1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="brno_ib1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mountains-2" /></template>
