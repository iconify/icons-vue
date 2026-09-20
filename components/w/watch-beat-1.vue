<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxnfvbayz.css';
import '../../css/h/h46e1ybha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxnfvbayz"/><path class="h46e1ybha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:watch-beat-1" /></template>
