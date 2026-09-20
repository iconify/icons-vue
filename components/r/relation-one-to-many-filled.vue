<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s91_41oli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s91_41oli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:relation-one-to-many-filled" /></template>
