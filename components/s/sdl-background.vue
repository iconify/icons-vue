<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ub-9wwbbn"/><path class="emkw7ezru"/><path class="z5fvzpzwy"/><path class="lmbmebb5x"/><path class="xm5n98bpd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sdl-background" /></template>
<style>
.emkw7ezru {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 12a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8-7.059c-3.958 0-7.059 3.101-7.059 7.059S8.042 19.059 12 19.059s7.059-3.101 7.059-7.059S15.958 4.941 12 4.941");
}

.ft5dv1b6b {
  fill: none;
}

.lmbmebb5x {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.741 7.59c-.137.123-1.812 1.252-1.459 3.182c.165.89 1.205 1.844 2.066 2.814c1.219 1.379 1.45 1.746 1.661 2.25c.518 1.232.061 2.493-.005 2.752c0 0 1.097-.805 1.309-1.882c.174-.904.131-1.139.06-1.548c-.173-.989-.926-1.812-1.806-2.72c-.87-.904-.95-.956-1.59-1.756c-.377-.47-.594-.922-.608-1.506c-.014-.851.485-1.694.367-1.586z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ub-9wwbbn {
  fill: var(--svg-color--474799, #474799);
  d: path("M24 0H0v24h24z");
}

.xm5n98bpd {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.584 6.767s.046.062.145.095c.132.047.33.056.485-.095c.141-.127.136-.32.09-.437a.34.34 0 0 0-.104-.141l.09-.095s.032.052.112.09a.47.47 0 0 0 .541-.118c.132-.141.104-.32.048-.428a1 1 0 0 0-.085-.127l.103-.099L15.52 8.74l-.49.443s-.437-.509-.908-.532a2.4 2.4 0 0 0-.72.047c-.254.056-.39.117-.696-.033c-.386-.193-.377-.588-.372-.795c.01-.165-.075-.26-.193-.264c-.103 0-.212.033-.235.193c-.047.33 0 .546.259.941c.25.372 1.223 1.27 1.543 1.624c.348.376.636.583 1.177 1.303c.376.49.88 1.19.88 2.047c0 .65-.203 1.045-.466 1.534c-.297.456-.653.87-1.059 1.233c.014-.033.301-.875.25-1.905c-.066-1.285-1.266-2.292-1.93-3.04c-.541-.603-1.016-1.064-1.558-1.77c-.932-1.214-.423-2.998-.423-2.998z");
}

.z5fvzpzwy {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.99 18.57l-3.472-3.266l1.468-1.398z");
}

</style>
