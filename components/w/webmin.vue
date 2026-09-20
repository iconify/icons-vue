<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w701jtbjt.css';
import '../../css/j/j8w5bp6yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w701jtbjt"/><path class="j8w5bp6yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webmin" /></template>
