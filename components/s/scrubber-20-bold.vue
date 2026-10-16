<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etp81e8xx.css';
import '../../css/s/smtmkz67c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="etp81e8xx"/><path class="smtmkz67c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scrubber-20-bold" /></template>
