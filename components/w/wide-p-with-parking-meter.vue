<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zii5sn5at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zii5sn5at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-p-with-parking-meter" /></template>
