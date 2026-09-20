<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcxm9nb7g.css';
import '../../css/o/o-c62h2ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcxm9nb7g"/><path class="o-c62h2ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-location-filled" /></template>
