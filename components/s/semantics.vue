<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek1gosbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek1gosbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:semantics" /></template>
