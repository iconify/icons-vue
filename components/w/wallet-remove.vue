<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/oj8w4xbvf.css';
import '../../css/t/terq8rrsy.css';
import '../../css/m/m8kjw2c8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oj8w4xbvf"/><path class="terq8rrsy"/><path class="m8kjw2c8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wallet-remove" /></template>
