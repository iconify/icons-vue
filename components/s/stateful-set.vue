<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyyeipb0v.css';
import '../../css/m/m8caoebdb.css';
import '../../css/c/cl10rdbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyyeipb0v"/><path class="m8caoebdb"/><path class="cl10rdbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:stateful-set" /></template>
