<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcnrjmbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":654,"height":1000};
const content = `<path class="tcnrjmbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:right-open" /></template>
