<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0le36bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r0le36bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-wearing-dress" /></template>
