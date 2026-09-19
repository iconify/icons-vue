<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb2yg1baz.css';
import '../../css/q/qzo006suv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="nb2yg1baz"/><path class="qzo006suv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sun-fill-12" /></template>
