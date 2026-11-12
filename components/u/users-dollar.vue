<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rarf-cbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rarf-cbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-dollar" /></template>
