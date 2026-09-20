<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o90fnvbiu.css';
import '../../css/q/qy0a994nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o90fnvbiu"/><path class="qy0a994nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:movie-fill" /></template>
