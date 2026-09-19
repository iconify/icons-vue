<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojrpslb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ojrpslb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:neos" /></template>
