<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dykvwujvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dykvwujvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-wearing-dress-beside-child-standing-beside-broadshouldered-person-standing" /></template>
