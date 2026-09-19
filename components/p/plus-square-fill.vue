<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y--pbs6ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y--pbs6ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:plus-square-fill" /></template>
