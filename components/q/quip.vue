<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-9a9geg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to-9a9geg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:quip" /></template>
