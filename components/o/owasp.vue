<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opz9j5bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opz9j5bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:owasp" /></template>
