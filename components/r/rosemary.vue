<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqsohmzgt.css';
import '../../css/p/pb4gmv60s.css';
import '../../css/m/millydbar.css';
import '../../css/h/hdqko0boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iqsohmzgt"/><path class="pb4gmv60s"/><path class="millydbar"/><path class="hdqko0boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:rosemary" /></template>
