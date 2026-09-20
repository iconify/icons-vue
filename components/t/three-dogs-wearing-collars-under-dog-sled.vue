<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmneqac1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pmneqac1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-dogs-wearing-collars-under-dog-sled" /></template>
