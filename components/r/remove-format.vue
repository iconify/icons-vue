<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6dn16dyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b6dn16dyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:remove-format" /></template>
