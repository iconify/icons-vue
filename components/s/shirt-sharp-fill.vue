<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5e1o8u-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5e1o8u-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shirt-sharp-fill" /></template>
