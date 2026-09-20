<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqy-zd.css';
import '../../css/o/osh3oc.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fade-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqy-zd"/><path class="osh3oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:pixelfed" /></template>
