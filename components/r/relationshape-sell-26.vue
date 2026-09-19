<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_dpo2bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="w_dpo2bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:relationshape-sell-26" /></template>
