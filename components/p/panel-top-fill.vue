<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ta8tb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ta8tb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-fill" /></template>
