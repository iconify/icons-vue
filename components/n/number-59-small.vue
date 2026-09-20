<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh7i4nfjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh7i4nfjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-59-small" /></template>
