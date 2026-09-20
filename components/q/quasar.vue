<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aree9-bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aree9-bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:quasar" /></template>
