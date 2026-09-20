<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x08_8nb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swap-driving-apps-wheel-sharp" /></template>
<style>
.x08_8nb3n {
  fill: currentColor;
  d: path("M8.5 20.29q-1.642-.711-2.86-1.93T3.71 15.5T3 11.997t.71-3.5T5.64 5.64T8.5 3.71Q10.142 3 12.003 3q1.86 0 3.5.71q1.64.711 2.858 1.93t1.929 2.857q.71 1.64.71 3.5t-.71 3.503q-.711 1.642-1.93 2.86t-2.857 1.93t-3.5.71t-3.503-.71m-.932-9.722q.24-.24.24-.568t-.24-.568T7 9.192t-.568.24t-.24.568t.24.568t.568.24t.568-.24m3-3q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m7 3q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m-4.502 2.498q.434-.433.434-1.066q0-.325-.129-.609q-.129-.283-.348-.514l1.75-4.446l-.932-.402l-1.783 4.471q-.635-.029-1.096.409T10.5 12q0 .633.434 1.066q.433.434 1.066.434t1.066-.434m4.15 4.98q-1.155-.767-2.493-1.156q-1.338-.39-2.723-.39t-2.723.39t-2.492 1.156l.903.646q.99-.576 2.081-.884T12 17.5t2.23.308t2.082.884z");
}

</style>
