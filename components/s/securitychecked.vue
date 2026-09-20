<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzolo-p4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="dzolo-p4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:securitychecked" /></template>
