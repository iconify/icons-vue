<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_vnwtbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v_vnwtbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-school-bus" /></template>
