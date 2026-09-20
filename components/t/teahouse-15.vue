<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpd7kl_ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rpd7kl_ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:teahouse-15" /></template>
