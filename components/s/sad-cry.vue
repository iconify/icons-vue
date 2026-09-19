<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmw12wbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="bmw12wbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:sad-cry" /></template>
