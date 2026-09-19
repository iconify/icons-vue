<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxo4hmbaa.css';
import '../../css/r/rf258g3jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rxo4hmbaa"/><path class="rf258g3jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:price-tag" /></template>
