<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6nfn3bmq.css';
import '../../css/d/d9itboj4b.css';
import '../../css/a/aqb2160dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h6nfn3bmq"/><path class="d9itboj4b"/><path class="aqb2160dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:xingtu" /></template>
