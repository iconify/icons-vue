<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g113u0-1c.css';
import '../../css/m/m8xzmqmih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g113u0-1c"/><path class="m8xzmqmih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soda-can-20" /></template>
