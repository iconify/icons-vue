<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5tjuwali.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5tjuwali"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:plus-24" /></template>
