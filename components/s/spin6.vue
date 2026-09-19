<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mycp4-b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="fil0 mycp4-b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:spin6" /></template>
