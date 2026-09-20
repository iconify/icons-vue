<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rah3vs0hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="rah3vs0hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:stamp" /></template>
