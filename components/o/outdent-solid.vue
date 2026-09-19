<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sycuzl5wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sycuzl5wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:outdent-solid" /></template>
