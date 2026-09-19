<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e73n2wbci.css';
import '../../css/t/ts2ygdnsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e73n2wbci"/><path class="ts2ygdnsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:return-up-forward-sharp" /></template>
