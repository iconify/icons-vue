<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rga3zb8al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-off-outline" /></template>
<style>
.rga3zb8al {
  fill: currentColor;
  d: path("m19.904 21.37l-8.285-8.335q-1.521.063-2.908.67T6.35 15.35l-1.023-1.034q.973-.974 2.273-1.67t2.735-.896L6.66 8.077q-1.14.448-2.364 1.249T2.1 11.1l-.985-1.034q.993-.993 2.163-1.813t2.26-1.3l-2.291-2.29l.708-.708l16.708 16.708zm-8.996-1.396q-.446-.449-.446-1.09q0-.646.446-1.092T12 17.346t1.092.446t.446 1.092q0 .641-.446 1.09T12 20.423t-1.092-.449M17.9 15.05l-.427-.427l-.427-.427l-2.08-2.08q.851.2 1.845.746t1.862 1.415zm4-3.95q-1.925-1.925-4.462-3.012T12 7q-.525 0-1.041.038q-.517.037-.959.112L8.72 5.87q.657-.166 1.458-.249T12 5.538q3.223 0 6.01 1.2t4.913 3.328z");
}

</style>
