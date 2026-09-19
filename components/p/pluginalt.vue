<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwj6s36cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="gwj6s36cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pluginalt" /></template>
