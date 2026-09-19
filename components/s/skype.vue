<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy_vm35sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gy_vm35sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:skype" /></template>
