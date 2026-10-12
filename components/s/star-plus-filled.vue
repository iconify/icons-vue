<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9tq9hbvj.css';
import '../../css/k/kjn-z4brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9tq9hbvj"/><path class="kjn-z4brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-plus-filled" /></template>
