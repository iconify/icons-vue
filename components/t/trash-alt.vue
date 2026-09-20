<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sinvatmqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sinvatmqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:trash-alt" /></template>
