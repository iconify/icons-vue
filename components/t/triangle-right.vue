<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec2i-oxwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ec2i-oxwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:triangle-right" /></template>
