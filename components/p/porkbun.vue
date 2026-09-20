<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvs3i2z5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvs3i2z5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:porkbun" /></template>
