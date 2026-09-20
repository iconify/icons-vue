<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovd1yub7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ovd1yub7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-with-heart" /></template>
