<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nskmalzgz.css';
import '../../css/v/v97u7ccna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nskmalzgz"/><path class="v97u7ccna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:side-nav-collapse" /></template>
