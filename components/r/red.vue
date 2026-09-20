<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf-1zmb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf-1zmb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:red" /></template>
