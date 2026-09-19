<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5riwrb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5riwrb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:question-circle-solid" /></template>
