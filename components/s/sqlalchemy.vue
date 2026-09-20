<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buvcqzozy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buvcqzozy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sqlalchemy" /></template>
