<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc0rw33ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc0rw33ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:margin-bottom" /></template>
