<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn1kni4jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="dn1kni4jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wifi" /></template>
