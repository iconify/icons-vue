<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-0h0cb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="g-0h0cb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:securityalt" /></template>
