<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov5v3-62v.css';
import '../../css/h/h-s431bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ov5v3-62v"/><path class="h-s431bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sqlalchemy" /></template>
