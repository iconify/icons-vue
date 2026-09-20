<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uls39h0tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uls39h0tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pocketbase" /></template>
