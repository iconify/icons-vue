<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5b5ddvql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5b5ddvql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:vinyl2-filled" /></template>
