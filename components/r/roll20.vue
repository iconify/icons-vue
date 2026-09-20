<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtc3gqdsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtc3gqdsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:roll20" /></template>
