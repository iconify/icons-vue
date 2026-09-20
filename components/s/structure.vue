<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyorfdtbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wyorfdtbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:structure" /></template>
