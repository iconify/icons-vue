<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1pyb518k.css';
import '../../css/b/bavhjmbgw.css';
import '../../css/k/kruzn2_tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b1pyb518k"/><path class="bavhjmbgw"/><path class="kruzn2_tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:money-exchange" /></template>
