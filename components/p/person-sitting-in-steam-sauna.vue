<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei34isb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ei34isb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sitting-in-steam-sauna" /></template>
