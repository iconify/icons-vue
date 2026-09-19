<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch25feblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ch25feblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:medium" /></template>
