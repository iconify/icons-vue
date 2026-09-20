<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqx37mbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="uqx37mbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:shoppingbag" /></template>
