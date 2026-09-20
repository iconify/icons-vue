<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce3ia3amw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce3ia3amw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:poly" /></template>
