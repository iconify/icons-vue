<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgdmlu84t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":896};
const content = `<path class="lgdmlu84t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:passwordalt" /></template>
