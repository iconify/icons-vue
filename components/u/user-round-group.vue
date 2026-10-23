<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suiwf7gvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suiwf7gvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-round-group" /></template>
