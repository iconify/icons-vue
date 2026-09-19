<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya5a489_p.css';
import '../../css/m/md0kk7b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya5a489_p"/><path class="md0kk7b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:waka-kotahi" /></template>
