<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d50lqeb2v.css';
import '../../css/b/b8ii2dbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":327.084};
const content = `<path class="d50lqeb2v"/><path class="b8ii2dbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mms" /></template>
