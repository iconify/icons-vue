<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqk4wvbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eqk4wvbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:porkbun-light" /></template>
