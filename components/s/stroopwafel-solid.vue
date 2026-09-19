<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hilrasb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hilrasb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:stroopwafel-solid" /></template>
