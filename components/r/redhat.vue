<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa6c9-14m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aa6c9-14m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:redhat" /></template>
