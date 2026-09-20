<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v65n5tbtm.css';
import '../../css/p/p06wdrbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v65n5tbtm"/><path class="p06wdrbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:reddit" /></template>
