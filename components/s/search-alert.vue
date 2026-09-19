<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inpj8acnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inpj8acnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:search-alert" /></template>
