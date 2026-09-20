<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s71wdfb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s71wdfb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:redmine" /></template>
