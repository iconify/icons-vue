<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esqfgjb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esqfgjb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:menu-alt-02" /></template>
