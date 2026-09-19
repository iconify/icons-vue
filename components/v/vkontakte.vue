<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ftu38ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="j7ftu38ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:vkontakte" /></template>
