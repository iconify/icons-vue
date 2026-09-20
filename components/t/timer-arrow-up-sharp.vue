<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebk6s_bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-arrow-up-sharp" /></template>
<style>
.ebk6s_bro {
  fill: currentColor;
  d: path("M4.207 17.13q-1.86-1.87-1.86-4.534t1.86-4.533t4.524-1.87q1.185 0 2.248.402q1.063.403 1.898 1.128l.954-.954l.688.689l-.934.953q.725.835 1.137 1.902t.413 2.283q0 2.663-1.87 4.534T8.73 19t-4.524-1.87M18.885 19V6.916L17.4 8.4l-.708-.708L19.385 5l2.692 2.692l-.713.708l-1.48-1.479V19zM6.807 4.77v-1h3.884v1zm1.423 8.134h1V9.096h-1z");
}

</style>
