<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4nuosbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4nuosbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-align-justify" /></template>
