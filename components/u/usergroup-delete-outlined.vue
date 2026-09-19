<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5w6ywn1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t5w6ywn1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:usergroup-delete-outlined" /></template>
