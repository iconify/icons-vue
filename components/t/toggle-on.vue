<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg6z7owzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kg6z7owzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:toggle-on" /></template>
