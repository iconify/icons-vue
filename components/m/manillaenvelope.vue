<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0msh_vzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":833,"height":1024};
const content = `<path class="m0msh_vzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:manillaenvelope" /></template>
