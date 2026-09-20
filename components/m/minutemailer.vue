<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za7vhlb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za7vhlb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:minutemailer" /></template>
