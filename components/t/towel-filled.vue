<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhqgeeukd.css';
import '../../css/g/g97n7gbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhqgeeukd"/><path class="g97n7gbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:towel-filled" /></template>
