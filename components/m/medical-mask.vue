<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x19w_acyj.css';
import '../../css/v/vpd7rkvil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x19w_acyj"/><path class="vpd7rkvil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:medical-mask" /></template>
