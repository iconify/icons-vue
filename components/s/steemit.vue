<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op2gj8b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op2gj8b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:steemit" /></template>
