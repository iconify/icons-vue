<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvdu31bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvdu31bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:target-3" /></template>
