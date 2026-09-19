<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omrj64z5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":740,"height":850};
const content = `<path class="omrj64z5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:pie" /></template>
