<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljrzvsbti.css';
import '../../css/o/ohubqmb2c.css';
import '../../css/x/xcd4ndbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljrzvsbti"/><path class="ohubqmb2c"/><path class="xcd4ndbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:tennisball-sharp" /></template>
