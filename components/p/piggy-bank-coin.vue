<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db0of5bxd.css';
import '../../css/n/ndxq0db7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="db0of5bxd"/><path class="ndxq0db7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:piggy-bank-coin" /></template>
