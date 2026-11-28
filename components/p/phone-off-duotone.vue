<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkk9n5bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkk9n5bpf primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phone-off-duotone" /></template>
