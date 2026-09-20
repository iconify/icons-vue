<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfbfy9biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tfbfy9biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-skype" /></template>
